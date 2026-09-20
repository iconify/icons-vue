<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbhnk0kri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbhnk0kri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-up-fill" /></template>
