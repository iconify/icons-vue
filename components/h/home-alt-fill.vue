<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guk9znuej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guk9znuej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-alt-fill" /></template>
