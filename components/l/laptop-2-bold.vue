<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2urmqbds.css';
import '../../css/e/ezj2uyggj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2urmqbds"/><path class="ezj2uyggj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-2-bold" /></template>
