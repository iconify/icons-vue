<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajsn0ftzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajsn0ftzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:divide" /></template>
