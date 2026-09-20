<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lflbifr_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lflbifr_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:customer-filled" /></template>
