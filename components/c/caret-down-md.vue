<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w18z5db_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w18z5db_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-down-md" /></template>
