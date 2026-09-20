<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm1099b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1099b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aa" /></template>
