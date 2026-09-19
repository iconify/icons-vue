<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udqwx6wsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udqwx6wsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-arrow-right-solid" /></template>
