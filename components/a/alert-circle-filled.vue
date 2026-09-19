<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y68jgrb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y68jgrb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alert-circle-filled" /></template>
