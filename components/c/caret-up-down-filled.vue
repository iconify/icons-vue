<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w06iw6b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w06iw6b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-up-down-filled" /></template>
