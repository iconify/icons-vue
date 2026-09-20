<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utjuaibbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utjuaibbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-line" /></template>
