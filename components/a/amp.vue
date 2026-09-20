<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmr0swbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmr0swbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:amp" /></template>
