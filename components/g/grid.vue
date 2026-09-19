<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn1iq6wxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gn1iq6wxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:grid" /></template>
