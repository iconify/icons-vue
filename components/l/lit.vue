<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de9n9ebhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de9n9ebhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lit" /></template>
