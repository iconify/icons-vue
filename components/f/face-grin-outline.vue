<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pln-rdb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pln-rdb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:face-grin-outline" /></template>
