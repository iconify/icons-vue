<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roquk4b2w.css';
import '../../css/t/tba9ohb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roquk4b2w"/><path class="tba9ohb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:credit-card" /></template>
