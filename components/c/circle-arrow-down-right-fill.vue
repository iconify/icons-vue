<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdlbvbcjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdlbvbcjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-down-right-fill" /></template>
