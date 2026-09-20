<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pimdvw83k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pimdvw83k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-heart" /></template>
