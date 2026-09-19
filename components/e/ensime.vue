<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwplii8cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":450,"height":512};
const content = `<path class="pwplii8cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ensime" /></template>
