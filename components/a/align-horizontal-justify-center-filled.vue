<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvg_1-o8n.css';
import '../../css/m/m0esjaiqj.css';
import '../../css/a/abtzwvxwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="uvg_1-o8n"/><rect class="m0esjaiqj"/><path class="abtzwvxwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-horizontal-justify-center-filled" /></template>
