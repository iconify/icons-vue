<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfrs8ublx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfrs8ublx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cabin-care" /></template>
