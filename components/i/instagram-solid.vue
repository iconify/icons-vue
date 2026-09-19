<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj0r58dgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj0r58dgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:instagram-solid" /></template>
