<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjp8bhb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjp8bhb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-list-numbers" /></template>
