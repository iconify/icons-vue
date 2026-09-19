<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidz9ubar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qidz9ubar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-three-quarter" /></template>
