<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z34kj1bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z34kj1bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:circle-check-solid" /></template>
