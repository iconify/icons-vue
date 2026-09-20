<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuw37nb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuw37nb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ear-listen-fill" /></template>
