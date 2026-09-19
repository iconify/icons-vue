<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5j85dd5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v5j85dd5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-error-fill-12" /></template>
