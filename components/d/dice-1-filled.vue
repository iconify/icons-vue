<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm8b7yb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm8b7yb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dice-1-filled" /></template>
