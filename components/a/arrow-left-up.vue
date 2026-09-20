<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz-eqn46t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rz-eqn46t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-up" /></template>
