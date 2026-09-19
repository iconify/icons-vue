<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3231hb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s3231hb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face5-filled" /></template>
