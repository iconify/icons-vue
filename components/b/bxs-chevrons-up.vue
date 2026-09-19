<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw56jtzlm.css';
import '../../css/i/i7gp9cbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw56jtzlm"/><path class="i7gp9cbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevrons-up" /></template>
