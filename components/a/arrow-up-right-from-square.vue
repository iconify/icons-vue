<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwgfh2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwgfh2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-up-right-from-square" /></template>
