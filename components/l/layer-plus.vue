<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae07h2byp.css';
import '../../css/a/a_f7wt5fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae07h2byp"/><path class="a_f7wt5fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:layer-plus" /></template>
