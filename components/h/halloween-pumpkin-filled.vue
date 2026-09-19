<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z88-oei-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z88-oei-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-pumpkin-filled" /></template>
