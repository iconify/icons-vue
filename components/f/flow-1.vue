<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea2dqbclq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea2dqbclq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flow-1" /></template>
