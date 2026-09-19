<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbf3dqbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbf3dqbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alarm-filled" /></template>
