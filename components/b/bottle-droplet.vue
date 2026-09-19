<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzdi1-b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="rzdi1-b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bottle-droplet" /></template>
