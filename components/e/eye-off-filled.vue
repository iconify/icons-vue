<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxg95ybdy.css';
import '../../css/k/kr-f3xbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxg95ybdy"/><path class="kr-f3xbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:eye-off-filled" /></template>
