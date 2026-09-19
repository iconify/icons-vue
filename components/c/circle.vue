<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amae8eb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amae8eb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:circle" /></template>
