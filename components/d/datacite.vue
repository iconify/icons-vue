<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oov1-gbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oov1-gbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:datacite" /></template>
