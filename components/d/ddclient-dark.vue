<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abrqmabzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abrqmabzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ddclient-dark" /></template>
