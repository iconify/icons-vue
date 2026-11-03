<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-_mvbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-_mvbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:edit-pencil-01" /></template>
