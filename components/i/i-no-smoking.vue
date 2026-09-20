<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-tedebsj.css';
import '../../css/t/tp-8ulbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m-tedebsj"/><path class="tp-8ulbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-no-smoking" /></template>
