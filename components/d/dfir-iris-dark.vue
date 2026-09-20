<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf3xb6b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qf3xb6b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dfir-iris-dark" /></template>
