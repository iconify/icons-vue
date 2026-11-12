<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw8q64y9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw8q64y9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceshelf-dark" /></template>
