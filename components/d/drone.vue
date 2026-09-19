<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4qxr-bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4qxr-bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:drone" /></template>
