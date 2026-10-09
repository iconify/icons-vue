<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-g74icta.css';
import '../../css/m/m743fhbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="m743fhbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-minus-20" /></template>
