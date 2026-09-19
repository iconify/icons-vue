<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9l-ttbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9l-ttbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:closuretemplate" /></template>
