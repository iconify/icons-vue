<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l07610gvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l07610gvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dify-light" /></template>
