<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1p82db_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a1p82db_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubbles-fill-20" /></template>
