<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blj85pqph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blj85pqph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-box-top-center" /></template>
