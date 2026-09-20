<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyiep3brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyiep3brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bed-flat" /></template>
