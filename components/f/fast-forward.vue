<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmpeiw39a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmpeiw39a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:fast-forward" /></template>
