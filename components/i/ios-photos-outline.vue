<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yup12tbhc.css';
import '../../css/t/txw5etdzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yup12tbhc"/><path class="txw5etdzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-photos-outline" /></template>
