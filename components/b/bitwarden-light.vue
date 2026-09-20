<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qji0dibyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qji0dibyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bitwarden-light" /></template>
