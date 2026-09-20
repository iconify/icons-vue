<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7_4gwb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7_4gwb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:collapse-solid" /></template>
