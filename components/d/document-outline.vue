<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z07rjrbqz.css';
import '../../css/m/m-h11vjnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z07rjrbqz"/><path class="m-h11vjnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document-outline" /></template>
