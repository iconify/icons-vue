<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmmf48b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmmf48b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:heart-dislike" /></template>
