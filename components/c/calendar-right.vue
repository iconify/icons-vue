<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftrvp1bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ftrvp1bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-right" /></template>
