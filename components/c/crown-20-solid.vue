<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyg5p4b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nyg5p4b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crown-20-solid" /></template>
