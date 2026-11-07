<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyxk3mbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyxk3mbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-broken" /></template>
