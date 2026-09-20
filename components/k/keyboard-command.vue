<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-p9n0bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-p9n0bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:keyboard-command" /></template>
