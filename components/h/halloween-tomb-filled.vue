<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7d34xbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7d34xbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-tomb-filled" /></template>
