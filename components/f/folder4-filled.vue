<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3nbb6b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3nbb6b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder4-filled" /></template>
