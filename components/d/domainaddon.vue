<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soc0mqopd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="soc0mqopd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:domainaddon" /></template>
