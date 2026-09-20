<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8u_thbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8u_thbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:emoji-fill" /></template>
