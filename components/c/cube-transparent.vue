<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enalfn1yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enalfn1yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube-transparent" /></template>
