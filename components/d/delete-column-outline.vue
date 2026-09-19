<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufw0hfimz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufw0hfimz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:delete-column-outline" /></template>
