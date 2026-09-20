<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqvm_7opk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqvm_7opk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:folder-share" /></template>
