<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxxqo73bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxxqo73bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-minus-sharp" /></template>
