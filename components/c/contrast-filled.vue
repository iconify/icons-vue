<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4oluribo.css';
import '../../css/c/c112rwb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4oluribo"/><path class="c112rwb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:contrast-filled" /></template>
