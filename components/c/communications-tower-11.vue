<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-edn5bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="s-edn5bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:communications-tower-11" /></template>
