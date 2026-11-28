<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrs4upb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrs4upb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flashlight-check" /></template>
