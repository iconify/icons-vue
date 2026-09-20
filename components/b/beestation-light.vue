<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfiofnb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dfiofnb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beestation-light" /></template>
