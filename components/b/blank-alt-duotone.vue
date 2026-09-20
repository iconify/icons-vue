<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdjq2-vym.css';
import '../../css/x/xgndkg1rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdjq2-vym"/><path class="xgndkg1rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:blank-alt-duotone" /></template>
