<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udafjeyph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udafjeyph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cent" /></template>
