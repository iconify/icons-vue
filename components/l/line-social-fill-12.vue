<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ers9nqbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ers9nqbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:line-social-fill-12" /></template>
