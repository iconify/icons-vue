<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha06gbbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ha06gbbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:filter-solid" /></template>
