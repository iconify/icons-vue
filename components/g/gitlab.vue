<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7r7hac8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7r7hac8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gitlab" /></template>
