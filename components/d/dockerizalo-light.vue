<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhkel2bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhkel2bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockerizalo-light" /></template>
