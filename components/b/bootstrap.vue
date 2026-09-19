<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/concw1lqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="concw1lqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bootstrap" /></template>
