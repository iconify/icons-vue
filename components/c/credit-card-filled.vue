<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye-jbqbha.css';
import '../../css/f/fzplxusck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-jbqbha"/><path clip-rule="evenodd" class="fzplxusck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:credit-card-filled" /></template>
