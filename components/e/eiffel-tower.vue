<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/env0utbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="env0utbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:eiffel-tower" /></template>
