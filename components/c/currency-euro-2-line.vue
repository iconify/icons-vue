<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avd8sacsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avd8sacsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-euro-2-line" /></template>
