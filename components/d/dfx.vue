<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8-5dqbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8-5dqbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dfx" /></template>
