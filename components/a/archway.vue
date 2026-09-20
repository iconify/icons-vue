<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afkq9obgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afkq9obgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:archway" /></template>
