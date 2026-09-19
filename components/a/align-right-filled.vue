<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi62yk3_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zi62yk3_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-right-filled" /></template>
