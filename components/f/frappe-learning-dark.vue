<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb0w0iykn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nb0w0iykn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-learning-dark" /></template>
