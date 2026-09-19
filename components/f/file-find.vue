<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtdpz00sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtdpz00sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-find" /></template>
