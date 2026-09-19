<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7tx4gznz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7tx4gznz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:building-solid" /></template>
