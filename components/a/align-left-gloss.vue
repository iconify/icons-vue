<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_4r47cdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_4r47cdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-left-gloss" /></template>
