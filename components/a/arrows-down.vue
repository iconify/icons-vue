<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_or1xp5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_or1xp5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrows-down" /></template>
