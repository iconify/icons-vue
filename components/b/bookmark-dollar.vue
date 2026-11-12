<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxb0y9l6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxb0y9l6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-dollar" /></template>
