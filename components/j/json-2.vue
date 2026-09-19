<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qquo4fqes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qquo4fqes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:json-2" /></template>
