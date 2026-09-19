<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t691w9ufv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t691w9ufv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chrome-cast" /></template>
