<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moj52yb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moj52yb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ars-technica" /></template>
