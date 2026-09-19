<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-5z9b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1-5z9b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:database-filled" /></template>
