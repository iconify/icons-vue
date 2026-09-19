<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huvje1kqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huvje1kqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heading-h1" /></template>
