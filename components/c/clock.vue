<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htc4simvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="htc4simvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:clock" /></template>
