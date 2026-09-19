<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hshhqwbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hshhqwbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-heart-filled" /></template>
