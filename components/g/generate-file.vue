<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqo929d9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqo929d9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:generate-file" /></template>
