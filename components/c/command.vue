<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfrdsfanz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfrdsfanz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:command" /></template>
