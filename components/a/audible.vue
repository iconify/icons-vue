<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq1tg9h7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jq1tg9h7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audible" /></template>
