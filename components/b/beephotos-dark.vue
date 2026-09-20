<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqpgh_bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oqpgh_bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beephotos-dark" /></template>
