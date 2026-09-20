<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go396ebfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="go396ebfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:box-fill" /></template>
