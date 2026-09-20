<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxg7xccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxg7xccaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bvg" /></template>
