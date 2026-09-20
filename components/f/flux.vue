<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_xkui35a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_xkui35a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:flux" /></template>
