<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us-2mi8ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="us-2mi8ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:lari-sign" /></template>
