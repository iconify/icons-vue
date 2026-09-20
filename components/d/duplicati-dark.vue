<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sztx2j67i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sztx2j67i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duplicati-dark" /></template>
