<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pao-nqbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pao-nqbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dollar-sign-fill" /></template>
