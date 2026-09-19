<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii7a4u0gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii7a4u0gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hyper" /></template>
