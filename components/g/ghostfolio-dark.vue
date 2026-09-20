<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5wonbc3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5wonbc3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghostfolio-dark" /></template>
