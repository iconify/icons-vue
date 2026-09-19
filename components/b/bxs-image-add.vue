<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_93su88i.css';
import '../../css/v/viznwcc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_93su88i"/><path class="viznwcc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-image-add" /></template>
