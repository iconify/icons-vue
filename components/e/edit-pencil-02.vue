<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chikk6bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chikk6bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:edit-pencil-02" /></template>
