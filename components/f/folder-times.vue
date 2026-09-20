<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn5z01lzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn5z01lzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-times" /></template>
