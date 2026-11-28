<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5nclzbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5nclzbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-zip-lock" /></template>
