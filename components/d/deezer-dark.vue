<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce7izibzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ce7izibzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deezer-dark" /></template>
