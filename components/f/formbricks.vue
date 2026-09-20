<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp319kbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp319kbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:formbricks" /></template>
