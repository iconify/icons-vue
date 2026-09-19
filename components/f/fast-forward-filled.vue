<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzv41yu8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzv41yu8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fast-forward-filled" /></template>
