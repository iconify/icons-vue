<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t732w_hqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t732w_hqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bevy" /></template>
