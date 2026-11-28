<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqbz-5bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqbz-5bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:club" /></template>
