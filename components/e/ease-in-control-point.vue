<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp3opab4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp3opab4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ease-in-control-point" /></template>
