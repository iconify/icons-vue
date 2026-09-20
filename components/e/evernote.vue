<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpy4g_b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpy4g_b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:evernote" /></template>
