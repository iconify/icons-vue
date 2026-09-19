<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt4uo0omy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt4uo0omy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-share-alt" /></template>
