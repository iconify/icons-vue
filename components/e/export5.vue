<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w57uk_h9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w57uk_h9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:export5" /></template>
