<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqvxjypmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqvxjypmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:closed-captioning-slash" /></template>
