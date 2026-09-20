<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soj-5vb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="soj-5vb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:magnifier-remove" /></template>
