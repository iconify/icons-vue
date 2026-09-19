<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwcsq9-ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iwcsq9-ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-1" /></template>
