<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzk00ybyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzk00ybyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-circle-solid" /></template>
