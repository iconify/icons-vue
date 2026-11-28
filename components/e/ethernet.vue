<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpfel9xrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gpfel9xrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ethernet" /></template>
