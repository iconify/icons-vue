<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3y_oxb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c3y_oxb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-exclamation-16-solid" /></template>
