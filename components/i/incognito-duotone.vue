<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9luvzb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9luvzb-k primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:incognito-duotone" /></template>
