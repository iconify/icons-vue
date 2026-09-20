<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gagwkz8je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gagwkz8je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:g" /></template>
