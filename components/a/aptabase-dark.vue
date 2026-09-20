<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amra5osci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amra5osci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aptabase-dark" /></template>
