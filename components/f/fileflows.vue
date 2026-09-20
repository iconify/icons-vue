<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be4hxabip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="be4hxabip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows" /></template>
