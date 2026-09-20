<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwp21cyvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwp21cyvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-colour-highlight" /></template>
