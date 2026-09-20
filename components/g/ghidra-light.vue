<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abv6fbbiq.css';
import '../../css/v/vy5mqsbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abv6fbbiq"/><path class="vy5mqsbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghidra-light" /></template>
