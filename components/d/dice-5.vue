<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vozuasbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vozuasbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-5" /></template>
