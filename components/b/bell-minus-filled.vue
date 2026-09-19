<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb3kqobhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb3kqobhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bell-minus-filled" /></template>
