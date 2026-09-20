<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv7f0p25w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv7f0p25w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:ellipsis-vertical-circle-solid" /></template>
