<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m006cx35p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":48};
const content = `<path class="m006cx35p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:latrine" /></template>
