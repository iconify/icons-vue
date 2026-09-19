<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teeoa7uhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="teeoa7uhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:couchbase-wordmark" /></template>
