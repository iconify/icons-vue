<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5w19n5ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5w19n5ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:live-fill" /></template>
