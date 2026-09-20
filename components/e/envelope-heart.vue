<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-saik79v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-saik79v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-heart" /></template>
