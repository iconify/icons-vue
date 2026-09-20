<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkkus2bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkkus2bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lightbulb" /></template>
