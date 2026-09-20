<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjciqdb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjciqdb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cobalt-dark" /></template>
