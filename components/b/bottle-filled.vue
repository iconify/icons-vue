<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-2s2sb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-2s2sb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bottle-filled" /></template>
