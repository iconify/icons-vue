<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puo4n5box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puo4n5box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:eye-closed" /></template>
