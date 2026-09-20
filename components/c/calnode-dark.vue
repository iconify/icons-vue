<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioy9bfb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ioy9bfb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calnode-dark" /></template>
