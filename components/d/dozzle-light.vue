<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wysvl9k5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wysvl9k5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dozzle-light" /></template>
