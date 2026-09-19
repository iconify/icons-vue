<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s36yk8bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s36yk8bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-align-middle" /></template>
