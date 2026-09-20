<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyll4mbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fyll4mbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-nc-eu" /></template>
