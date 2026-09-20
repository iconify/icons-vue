<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of2vos27f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="of2vos27f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:bullseye" /></template>
