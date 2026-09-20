<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruzt6bb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ruzt6bb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kimai-dark" /></template>
