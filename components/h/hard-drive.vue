<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsmhz7bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jsmhz7bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:hard-drive" /></template>
