<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq85roq9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq85roq9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jotty-light" /></template>
