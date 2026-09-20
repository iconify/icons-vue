<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1x3wj3gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1x3wj3gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flow-line-fill" /></template>
