<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul6cc9b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ul6cc9b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fast-forward" /></template>
