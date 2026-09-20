<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heqw8lblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="heqw8lblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:header-1" /></template>
