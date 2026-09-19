<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm5l_ww-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm5l_ww-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-compare" /></template>
