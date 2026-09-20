<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1u5zqbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1u5zqbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:formula" /></template>
