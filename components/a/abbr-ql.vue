<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljd0xbcvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ljd0xbcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:abbr-ql" /></template>
