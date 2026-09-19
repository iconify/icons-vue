<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi1kkcb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi1kkcb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:edit-outline" /></template>
