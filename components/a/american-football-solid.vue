<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9t6t-b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9t6t-b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:american-football-solid" /></template>
