<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmsy48vjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmsy48vjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:capsule" /></template>
