<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwuzhri0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pwuzhri0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-left-up-filled" /></template>
