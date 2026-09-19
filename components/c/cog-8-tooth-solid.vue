<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agu67jb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="agu67jb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cog-8-tooth-solid" /></template>
