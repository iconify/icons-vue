<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp0adhykb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp0adhykb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alert-triangle-filled" /></template>
