<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkk3sjblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="nkk3sjblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-bar" /></template>
