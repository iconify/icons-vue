<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afpetgbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afpetgbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:button" /></template>
