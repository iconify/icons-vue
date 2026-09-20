<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lij2n1bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lij2n1bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:front" /></template>
