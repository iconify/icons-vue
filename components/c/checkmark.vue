<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8uoz3bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8uoz3bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:checkmark" /></template>
