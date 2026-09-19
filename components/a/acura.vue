<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxner0b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxner0b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:acura" /></template>
