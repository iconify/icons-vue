<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdrb4cbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdrb4cbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter" /></template>
