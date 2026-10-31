<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yniq5f4ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yniq5f4ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist-20-solid" /></template>
