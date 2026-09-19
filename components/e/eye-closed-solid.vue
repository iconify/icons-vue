<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybntw-bao.css';
import '../../css/u/ut2il9b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybntw-bao"/><path class="ut2il9b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:eye-closed-solid" /></template>
