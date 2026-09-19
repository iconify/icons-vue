<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prn2q9l7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="prn2q9l7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:confetti" /></template>
