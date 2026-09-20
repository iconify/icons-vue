<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afjtceb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="afjtceb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:blender" /></template>
