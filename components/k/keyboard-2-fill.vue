<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyvkoiyys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyvkoiyys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyboard-2-fill" /></template>
