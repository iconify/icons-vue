<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0h8p0bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m0h8p0bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:hourglass-end" /></template>
