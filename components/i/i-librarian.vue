<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooy89kzvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ooy89kzvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:i-librarian" /></template>
