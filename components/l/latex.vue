<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewat9cc6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewat9cc6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:latex" /></template>
