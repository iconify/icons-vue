<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uamfscbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":511.999,"height":511.999};
const content = `<path class="uamfscbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:docz" /></template>
