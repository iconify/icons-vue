<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8o-2rgnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8o-2rgnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:burger" /></template>
