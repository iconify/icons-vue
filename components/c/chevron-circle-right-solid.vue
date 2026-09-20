<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc4huuc1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vc4huuc1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chevron-circle-right-solid" /></template>
