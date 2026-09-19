<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hib7fibeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hib7fibeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:json-ld1" /></template>
