<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx2r51bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx2r51bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-2-line" /></template>
