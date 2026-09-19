<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6sel__is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":438,"height":512};
const content = `<path class="q6sel__is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dragula" /></template>
