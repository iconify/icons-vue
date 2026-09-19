<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqalrk6gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqalrk6gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lunch" /></template>
