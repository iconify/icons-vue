<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9rhm9n5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9rhm9n5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airtrail-dark" /></template>
