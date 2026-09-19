<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0scw1b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="x0scw1b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:heart" /></template>
