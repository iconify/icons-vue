<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv6-mibuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv6-mibuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:file-diff" /></template>
