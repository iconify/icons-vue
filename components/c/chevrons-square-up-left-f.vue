<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g97m8-h2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="g97m8-h2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-square-up-left-f" /></template>
