<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-x_9nb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-x_9nb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:flag-light" /></template>
