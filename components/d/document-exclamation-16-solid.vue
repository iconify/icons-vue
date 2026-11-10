<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0ko-764v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h0ko-764v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-exclamation-16-solid" /></template>
