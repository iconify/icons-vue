<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_to3pbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_to3pbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-docs" /></template>
