<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwa8trwny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qwa8trwny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:key" /></template>
