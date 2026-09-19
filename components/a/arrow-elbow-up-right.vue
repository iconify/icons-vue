<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-42gfrws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-42gfrws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-elbow-up-right" /></template>
