<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hve_623ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hve_623ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-right" /></template>
