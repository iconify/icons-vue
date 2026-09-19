<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd8xp2a-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zd8xp2a-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:keyboard-off-filled" /></template>
