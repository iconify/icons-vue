<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-5a6yozc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v-5a6yozc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crown-16-solid" /></template>
