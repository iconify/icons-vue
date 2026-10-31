<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq857obgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sq857obgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headphones-slash-16-solid" /></template>
