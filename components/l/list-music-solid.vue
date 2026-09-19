<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpvc8lxor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpvc8lxor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:list-music-solid" /></template>
