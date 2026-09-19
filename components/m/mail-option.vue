<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxt7gwb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxt7gwb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:mail-option" /></template>
