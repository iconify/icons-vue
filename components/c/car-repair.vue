<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evn57iodh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="evn57iodh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-repair" /></template>
