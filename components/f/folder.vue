<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2jf4zb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2jf4zb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:folder" /></template>
