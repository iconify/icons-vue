<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsuadg_ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xsuadg_ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:box-dark" /></template>
