<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x115p3bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x115p3bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:inst" /></template>
