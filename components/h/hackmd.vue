<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx9va6bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx9va6bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hackmd" /></template>
