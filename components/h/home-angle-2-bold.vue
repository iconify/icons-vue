<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk5-qvpov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk5-qvpov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-angle-2-bold" /></template>
