<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w-1c8gqjv.css';
import '../../css/a/a73y9lsqi.css';
import '../../css/a/avujdqbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w-1c8gqjv"/><path class="a73y9lsqi"/><path class="avujdqbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bed-double" /></template>
