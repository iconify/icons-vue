<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax27h5ulz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ax27h5ulz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:config" /></template>
