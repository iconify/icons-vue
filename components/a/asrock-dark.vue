<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go4x3ob7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="go4x3ob7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asrock-dark" /></template>
