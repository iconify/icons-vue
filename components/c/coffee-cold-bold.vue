<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl35jpbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl35jpbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coffee-cold-bold" /></template>
