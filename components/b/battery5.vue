<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oav6wl84e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oav6wl84e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:battery5" /></template>
