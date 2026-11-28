<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjma9vazq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjma9vazq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:key-refresh" /></template>
