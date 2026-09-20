<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag_t9i1ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag_t9i1ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-rust" /></template>
