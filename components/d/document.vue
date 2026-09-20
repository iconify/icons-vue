<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwq7_02iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwq7_02iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:document" /></template>
