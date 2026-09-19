<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj8myni9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj8myni9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-text-justify-left" /></template>
