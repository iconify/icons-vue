<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmxkzsb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmxkzsb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:grid-plus-solid" /></template>
