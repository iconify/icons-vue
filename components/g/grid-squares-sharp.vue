<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abw1ukz-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abw1ukz-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-sharp" /></template>
