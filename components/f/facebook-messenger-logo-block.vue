<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckwbwfbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckwbwfbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:facebook-messenger-logo-block" /></template>
