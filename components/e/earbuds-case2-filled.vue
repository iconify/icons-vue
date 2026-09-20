<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x27ye4o8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x27ye4o8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-case2-filled" /></template>
