<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whrhf5bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whrhf5bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:lightbulb" /></template>
