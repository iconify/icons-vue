<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agdg56brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agdg56brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:face-smile-filled" /></template>
