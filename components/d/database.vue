<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqtxu3bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqtxu3bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:database" /></template>
