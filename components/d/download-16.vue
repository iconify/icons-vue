<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a05-frb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a05-frb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:download-16" /></template>
