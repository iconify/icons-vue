<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx8ztij1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8ztij1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:dots-vertical-outline" /></template>
