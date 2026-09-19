<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7jhm504f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="b7jhm504f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-fill-12" /></template>
