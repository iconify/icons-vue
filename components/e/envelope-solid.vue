<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgs0yzbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xgs0yzbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:envelope-solid" /></template>
