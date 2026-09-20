<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1lszzbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1lszzbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-check-fill" /></template>
