<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-2e2xgge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-2e2xgge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anki-light" /></template>
