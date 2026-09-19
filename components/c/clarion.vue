<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywfwksb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywfwksb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:clarion" /></template>
