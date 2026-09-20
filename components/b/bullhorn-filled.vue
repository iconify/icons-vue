<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2q28wxdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2q28wxdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bullhorn-filled" /></template>
