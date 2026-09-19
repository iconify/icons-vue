<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i48rb5bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i48rb5bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:linkedin" /></template>
