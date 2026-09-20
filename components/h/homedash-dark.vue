<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_54rbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oe_54rbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:homedash-dark" /></template>
