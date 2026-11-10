<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5yuehbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o5yuehbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:document-exclamation-20-solid" /></template>
