<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3mevab6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3mevab6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:code-fork-solid" /></template>
