<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0c-dyboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o0c-dyboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:infinity-16-solid" /></template>
