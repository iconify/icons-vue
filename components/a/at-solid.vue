<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alk-0vllj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="alk-0vllj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:at-solid" /></template>
