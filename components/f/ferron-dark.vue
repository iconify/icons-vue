<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4oxcdcli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4oxcdcli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferron-dark" /></template>
