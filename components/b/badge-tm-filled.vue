<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hafxgworf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hafxgworf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-tm-filled" /></template>
