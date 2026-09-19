<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urmq5bc6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="urmq5bc6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:girl-angry" /></template>
