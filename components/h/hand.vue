<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aadmuy87f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aadmuy87f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hand" /></template>
