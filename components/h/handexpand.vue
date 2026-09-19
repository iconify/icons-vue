<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujcg1dbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ujcg1dbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handexpand" /></template>
