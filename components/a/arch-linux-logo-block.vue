<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9_-_eiow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9_-_eiow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:arch-linux-logo-block" /></template>
