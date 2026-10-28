<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pru0h0bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pru0h0bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:laptop" /></template>
