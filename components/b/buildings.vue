<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fct5sud1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fct5sud1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:buildings" /></template>
