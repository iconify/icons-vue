<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6ds70j6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="o6ds70j6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:etsy" /></template>
