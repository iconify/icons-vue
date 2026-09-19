<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_rzwjeht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_rzwjeht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hop" /></template>
