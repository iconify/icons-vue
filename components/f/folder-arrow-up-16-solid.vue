<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fekbzqbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fekbzqbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-arrow-up-16-solid" /></template>
