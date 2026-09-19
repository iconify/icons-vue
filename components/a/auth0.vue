<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq8y0r2ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aq8y0r2ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:auth0" /></template>
