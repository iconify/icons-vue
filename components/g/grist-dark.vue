<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8eptqggo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u8eptqggo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grist-dark" /></template>
