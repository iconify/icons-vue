<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah5i6mb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah5i6mb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-clipboard" /></template>
