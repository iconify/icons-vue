<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v40au7b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v40au7b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cetusguard-dark" /></template>
