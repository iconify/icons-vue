<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqo9-i3ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqo9-i3ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cooling-square-solid" /></template>
