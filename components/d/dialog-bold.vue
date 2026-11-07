<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-a8ibbxe.css';
import '../../css/y/y2bl_ob4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-a8ibbxe"/><path clip-rule="evenodd" class="y2bl_ob4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-bold" /></template>
