<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m21j3qb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m21j3qb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bullet-list-solid" /></template>
