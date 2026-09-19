<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz2mxftjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz2mxftjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dental-forceps-filled" /></template>
