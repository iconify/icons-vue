<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tterhvcih.css';
import '../../css/g/gi416ibwv.css';
import '../../css/j/jzjrs5bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer tterhvcih"/><path class="duoicon-primary-layer gi416ibwv"/><path class="duoicon-primary-layer jzjrs5bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:id-card" /></template>
