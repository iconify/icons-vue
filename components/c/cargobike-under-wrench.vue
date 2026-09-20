<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp8co0bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pp8co0bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-under-wrench" /></template>
