<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb9vjab-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="kb9vjab-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-alt-rm-o" /></template>
