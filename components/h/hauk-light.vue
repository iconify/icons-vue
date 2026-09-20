<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtz5kobml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtz5kobml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hauk-light" /></template>
