<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htifq4bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="htifq4bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-e" /></template>
