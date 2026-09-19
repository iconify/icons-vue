<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4on82bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4on82bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-cancel-filled" /></template>
