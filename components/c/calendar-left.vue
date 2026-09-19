<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj6ork7js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj6ork7js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-left" /></template>
