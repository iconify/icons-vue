<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xax_3jbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xax_3jbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:indeed" /></template>
