<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nup15fx8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nup15fx8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:building2" /></template>
