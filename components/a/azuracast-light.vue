<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pefbi7b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pefbi7b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:azuracast-light" /></template>
