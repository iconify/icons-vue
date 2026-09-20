<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbr4ir6uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbr4ir6uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-finger-fill" /></template>
