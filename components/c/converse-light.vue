<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scg3cibim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scg3cibim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:converse-light" /></template>
