<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku37lsbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ku37lsbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:information-square-fill" /></template>
