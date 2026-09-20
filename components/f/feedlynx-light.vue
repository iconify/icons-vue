<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icg58v2mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="icg58v2mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feedlynx-light" /></template>
