<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhdzintgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhdzintgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codereview" /></template>
