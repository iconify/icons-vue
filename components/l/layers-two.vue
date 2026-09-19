<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5j9tpbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5j9tpbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:layers-two" /></template>
