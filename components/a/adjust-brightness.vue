<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akc8dfwwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akc8dfwwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:adjust-brightness" /></template>
