<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmnxvqbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmnxvqbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-lightning-filled" /></template>
