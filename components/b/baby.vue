<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhe3r6bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jhe3r6bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:baby" /></template>
