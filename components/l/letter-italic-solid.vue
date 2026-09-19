<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p66jx1beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p66jx1beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:letter-italic-solid" /></template>
