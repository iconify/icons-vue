<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkzn81bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkzn81bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-delete-fill" /></template>
