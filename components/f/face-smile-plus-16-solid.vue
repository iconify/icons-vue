<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8qsur3ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x8qsur3ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-smile-plus-16-solid" /></template>
