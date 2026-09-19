<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-9b-jsve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-9b-jsve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:contrast" /></template>
