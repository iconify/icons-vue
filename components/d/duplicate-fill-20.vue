<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usahcrb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="usahcrb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:duplicate-fill-20" /></template>
