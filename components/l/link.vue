<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c44pee.css';
import '../../css/s/so-from-28.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c44pee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:link" /></template>
