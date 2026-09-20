<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c43qe1bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c43qe1bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dice-4-solid" /></template>
