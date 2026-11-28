<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3pz8gwni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3pz8gwni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:key" /></template>
