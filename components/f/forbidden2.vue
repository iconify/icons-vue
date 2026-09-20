<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3bj4mojt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3bj4mojt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forbidden2" /></template>
