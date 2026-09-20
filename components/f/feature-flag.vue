<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_o-v-b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_o-v-b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:feature-flag" /></template>
