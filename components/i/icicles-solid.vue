<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akkw_4bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="akkw_4bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:icicles-solid" /></template>
