<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzji8fgvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzji8fgvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:edit-square" /></template>
