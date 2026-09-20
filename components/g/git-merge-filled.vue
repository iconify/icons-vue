<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlu42j8ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlu42j8ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-merge-filled" /></template>
