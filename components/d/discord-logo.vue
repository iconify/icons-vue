<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wanl34gha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wanl34gha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:discord-logo" /></template>
