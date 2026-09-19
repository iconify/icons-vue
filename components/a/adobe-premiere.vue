<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oap-5zu8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oap-5zu8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adobe-premiere" /></template>
