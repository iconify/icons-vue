<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stse3cnyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stse3cnyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arow-to-up-fill" /></template>
