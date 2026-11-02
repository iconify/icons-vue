<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chfadgb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chfadgb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:front-fog-lights-line" /></template>
