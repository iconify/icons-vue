<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-mi1jb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-mi1jb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-noodles-alt-filled" /></template>
