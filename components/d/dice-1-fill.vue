<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wurk_8s_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wurk_8s_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-1-fill" /></template>
