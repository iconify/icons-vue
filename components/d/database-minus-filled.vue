<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wllbo2bcu.css';
import '../../css/g/ge98ujwjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wllbo2bcu"/><path class="ge98ujwjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-minus-filled" /></template>
