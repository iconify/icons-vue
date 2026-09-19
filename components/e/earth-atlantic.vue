<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1jdi4cpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="d1jdi4cpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-atlantic" /></template>
