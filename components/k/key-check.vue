<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnk4ipbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnk4ipbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:key-check" /></template>
