<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur72ib6mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ur72ib6mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filezilla-dark" /></template>
