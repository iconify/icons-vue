<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgugrkbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgugrkbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-badge-horizontal-outline" /></template>
