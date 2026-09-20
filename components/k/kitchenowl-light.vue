<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf5_hobel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf5_hobel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kitchenowl-light" /></template>
