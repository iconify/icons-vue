<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyig9820h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cyig9820h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:biltema-light" /></template>
