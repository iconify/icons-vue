<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukw3-vb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ukw3-vb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-3-fill" /></template>
