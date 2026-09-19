<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohlt3tb5l.css';
import '../../css/n/njpi2rhkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohlt3tb5l"/><path class="njpi2rhkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:code-deploy-outlined" /></template>
