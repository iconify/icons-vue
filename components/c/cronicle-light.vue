<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ai52npl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9ai52npl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cronicle-light" /></template>
