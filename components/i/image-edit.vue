<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqk_9joly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqk_9joly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-edit" /></template>
