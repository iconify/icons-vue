<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxkmnwb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxkmnwb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase" /></template>
