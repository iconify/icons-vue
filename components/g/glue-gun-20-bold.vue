<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6h9w5hey.css';
import '../../css/s/sn5c15bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f6h9w5hey"/><path class="sn5c15bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:glue-gun-20-bold" /></template>
