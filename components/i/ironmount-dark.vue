<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxmzs5b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxmzs5b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ironmount-dark" /></template>
