<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kury_foqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kury_foqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:attention-solid-sm" /></template>
