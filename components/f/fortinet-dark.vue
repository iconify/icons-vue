<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss9riwbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ss9riwbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fortinet-dark" /></template>
