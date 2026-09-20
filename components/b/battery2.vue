<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahw0mccqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ahw0mccqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:battery2" /></template>
