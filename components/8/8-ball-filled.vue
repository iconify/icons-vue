<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8xfwqbqk.css';
import '../../css/i/i7-t02b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8xfwqbqk"/><path class="i7-t02b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:8-ball-filled" /></template>
