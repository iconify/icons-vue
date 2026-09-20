<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9vl9objf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s9vl9objf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:invision" /></template>
