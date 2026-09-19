<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsuy7qb9u.css';
import '../../css/i/if0ri8-so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsuy7qb9u"/><path class="if0ri8-so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:flexbicep" /></template>
