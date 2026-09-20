<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd97r8uzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sd97r8uzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:catalog-checkmark" /></template>
