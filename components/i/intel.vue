<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm99wgorg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm99wgorg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:intel" /></template>
