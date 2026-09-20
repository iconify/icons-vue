<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyj71nbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hyj71nbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bend" /></template>
