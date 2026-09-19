<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab3_j_b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab3_j_b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beehiiv-filled" /></template>
