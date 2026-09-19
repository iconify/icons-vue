<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz00pjbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":718,"height":709};
const content = `<path class="tz00pjbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:magic" /></template>
