<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abz4jnh1h.css';
import '../../css/f/f_bgirb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="abz4jnh1h"/><path class="f_bgirb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-company-filled" /></template>
