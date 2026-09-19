<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s16trob1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s16trob1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:alien-monster-small" /></template>
