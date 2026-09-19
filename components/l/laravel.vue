<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzc_ihq3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":498,"height":512};
const content = `<path class="bzc_ihq3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:laravel" /></template>
