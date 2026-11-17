<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4wh_8bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y4wh_8bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chirpstack-light" /></template>
