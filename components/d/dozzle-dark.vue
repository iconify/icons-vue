<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxg8a_oyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxg8a_oyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dozzle-dark" /></template>
