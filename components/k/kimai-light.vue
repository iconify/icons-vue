<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl0z4qqxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sl0z4qqxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kimai-light" /></template>
