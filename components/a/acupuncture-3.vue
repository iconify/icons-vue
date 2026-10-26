<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv2yqwsyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yv2yqwsyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:acupuncture-3" /></template>
