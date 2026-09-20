<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_ffkvbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_ffkvbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-sharp-fill" /></template>
