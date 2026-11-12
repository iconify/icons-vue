<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_fvxx96a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_fvxx96a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kherad-light" /></template>
