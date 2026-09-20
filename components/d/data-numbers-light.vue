<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo453mk3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jo453mk3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:data-numbers-light" /></template>
