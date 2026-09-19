<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gknle0bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gknle0bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:electric-light-bulb-small" /></template>
