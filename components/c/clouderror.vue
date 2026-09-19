<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oib75js9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oib75js9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:clouderror" /></template>
