<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/athgqh_ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="athgqh_ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:dumpster-thin" /></template>
