<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_f9b70gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_f9b70gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airtable-dark" /></template>
