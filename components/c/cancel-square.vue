<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9d_8tvzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9d_8tvzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cancel-square" /></template>
