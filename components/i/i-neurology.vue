<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfvs4195e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hfvs4195e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-neurology" /></template>
