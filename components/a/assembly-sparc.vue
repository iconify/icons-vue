<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh8f0lv2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sh8f0lv2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-sparc" /></template>
