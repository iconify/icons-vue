<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abfudubwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="abfudubwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-arrow-path-16-solid" /></template>
