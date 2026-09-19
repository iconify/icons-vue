<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toj71gdzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toj71gdzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-circle-settings" /></template>
