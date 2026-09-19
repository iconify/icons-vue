<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddqbdrr6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddqbdrr6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-list-solid" /></template>
