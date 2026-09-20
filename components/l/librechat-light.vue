<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuo4hqbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iuo4hqbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librechat-light" /></template>
