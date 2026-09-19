<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c--5i5fyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c--5i5fyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-right-up" /></template>
