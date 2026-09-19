<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7oq3hboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7oq3hboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloud-download-sharp" /></template>
