<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i817_ebjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i817_ebjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-center-outline" /></template>
