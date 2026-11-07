<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz4ipxy5n.css';
import '../../css/h/hu27cibfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz4ipxy5n"/><path class="hu27cibfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-bold" /></template>
