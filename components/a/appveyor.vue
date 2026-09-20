<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr6vqbl-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6vqbl-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:appveyor" /></template>
