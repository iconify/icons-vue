<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f048az1re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f048az1re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bucket" /></template>
