<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqreai28o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":272,"height":432};
const content = `<path class="kqreai28o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:google-old" /></template>
