<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evhrrmisg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="evhrrmisg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gift-16" /></template>
