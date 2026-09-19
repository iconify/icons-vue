<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adoz3-3sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adoz3-3sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-indesign" /></template>
