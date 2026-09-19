<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rro1-sbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":472};
const content = `<path class="rro1-sbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:filter" /></template>
