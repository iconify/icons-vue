<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st2ftqbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="st2ftqbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alert-triangle" /></template>
