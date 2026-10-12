<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvs93ubio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvs93ubio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-pull-request-create-arrow-filled" /></template>
