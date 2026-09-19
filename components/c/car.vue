<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwxp4tvzv.css';
import '../../css/d/dyto25hnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer nwxp4tvzv"/><path class="duoicon-primary-layer dyto25hnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:car" /></template>
