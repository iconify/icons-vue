<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyisdvg4m.css';
import '../../css/i/il_8vobti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyisdvg4m"/><path class="il_8vobti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess" /></template>
