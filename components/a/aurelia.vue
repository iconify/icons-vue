<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_1rld2kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_1rld2kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:aurelia" /></template>
