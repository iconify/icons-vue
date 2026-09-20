<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lda1ajbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lda1ajbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-left-double-s" /></template>
