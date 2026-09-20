<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iipafdbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iipafdbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-x" /></template>
