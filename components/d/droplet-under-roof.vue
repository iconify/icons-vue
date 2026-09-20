<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozyg45bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ozyg45bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-under-roof" /></template>
