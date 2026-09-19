<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqur7u31c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":448};
const content = `<path class="gqur7u31c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:arrow-down" /></template>
