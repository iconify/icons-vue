<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_bjbqbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_bjbqbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-box-line" /></template>
