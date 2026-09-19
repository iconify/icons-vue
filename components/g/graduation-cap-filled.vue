<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klpb0dbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klpb0dbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:graduation-cap-filled" /></template>
