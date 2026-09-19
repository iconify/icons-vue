<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to07rdbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to07rdbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:checkbox-check" /></template>
