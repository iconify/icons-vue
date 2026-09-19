<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id_2uy04o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="id_2uy04o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:center-focus-weak" /></template>
