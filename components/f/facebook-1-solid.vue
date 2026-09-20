<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3cwk-ews.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n3cwk-ews"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:facebook-1-solid" /></template>
