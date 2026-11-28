<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs3m8nkkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs3m8nkkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dice-6" /></template>
