<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ajhqn1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ajhqn1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jellyfin" /></template>
