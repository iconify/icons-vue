<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_10jfv9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="i_10jfv9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:cog" /></template>
