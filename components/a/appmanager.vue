<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te1jx8dgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te1jx8dgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:appmanager" /></template>
