<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njgjqzbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="njgjqzbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:eye-fill" /></template>
