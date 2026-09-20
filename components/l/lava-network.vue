<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5azz4pov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5azz4pov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lava-network" /></template>
