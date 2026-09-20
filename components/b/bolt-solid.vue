<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn-tu7bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jn-tu7bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bolt-solid" /></template>
