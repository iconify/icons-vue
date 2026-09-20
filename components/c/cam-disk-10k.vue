<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3qjh-7lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3qjh-7lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cam-disk-10k" /></template>
