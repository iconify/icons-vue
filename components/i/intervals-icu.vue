<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f02lo6bya.css';
import '../../css/b/bdrh4zbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":462.9,"height":462.9};
const content = `<circle class="f02lo6bya"/><path class="bdrh4zbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:intervals-icu" /></template>
