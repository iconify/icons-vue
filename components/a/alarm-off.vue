<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef35mebft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ef35mebft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alarm-off" /></template>
