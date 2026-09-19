<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h31609_ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h31609_ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:bbox-alt" /></template>
