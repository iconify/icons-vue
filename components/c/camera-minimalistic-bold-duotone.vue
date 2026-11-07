<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlx90jb3u.css';
import '../../css/x/x3ekvxvds.css';
import '../../css/e/eo14_jw6u.css';
import '../../css/c/cusbmcc7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlx90jb3u"/><path clip-rule="evenodd" class="x3ekvxvds"/><path class="eo14_jw6u"/><path class="cusbmcc7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-minimalistic-bold-duotone" /></template>
