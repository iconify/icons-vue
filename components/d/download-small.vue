<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmbw-t3wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nmbw-t3wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:download-small" /></template>
