<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lplg4im9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lplg4im9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:heart-broken" /></template>
