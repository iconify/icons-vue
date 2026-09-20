<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv3fe1b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv3fe1b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:corner-left-down" /></template>
