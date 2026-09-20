<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gurdrgddr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":124,"height":36};
const content = `<path class="gurdrgddr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anker" /></template>
