<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbj9szb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbj9szb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-text-center" /></template>
