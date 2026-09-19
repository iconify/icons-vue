<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ropm3r5qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ropm3r5qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:birthday-cake-filled" /></template>
