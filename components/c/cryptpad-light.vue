<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymzz4rb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymzz4rb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cryptpad-light" /></template>
