<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb4xqclor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gb4xqclor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jupiterone-light" /></template>
