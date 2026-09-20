<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j58-_kbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j58-_kbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:emoji-circle-filled" /></template>
