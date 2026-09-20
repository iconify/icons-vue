<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skn_peb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skn_peb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anythingllm-dark" /></template>
