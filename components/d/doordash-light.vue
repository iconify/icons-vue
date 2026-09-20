<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6bb6d7lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6bb6d7lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doordash-light" /></template>
