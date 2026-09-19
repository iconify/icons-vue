<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mstj7kszp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":961};
const content = `<path class="mstj7kszp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:camel" /></template>
