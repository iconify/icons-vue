<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpeg90bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vpeg90bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hangul-small" /></template>
