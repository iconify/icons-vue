<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a22os6vlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a22os6vlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-sort-fill" /></template>
