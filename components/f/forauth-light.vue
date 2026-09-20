<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8y_cqlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz8y_cqlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forauth-light" /></template>
