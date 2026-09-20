<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jekm3z_ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jekm3z_ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hammer-alt-line" /></template>
