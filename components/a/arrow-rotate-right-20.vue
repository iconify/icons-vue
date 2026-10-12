<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba2z7ll-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ba2z7ll-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-rotate-right-20" /></template>
