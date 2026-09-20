<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnj__0ttb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnj__0ttb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cactus-off" /></template>
