<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmdxbxbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmdxbxbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:contrast-solid" /></template>
