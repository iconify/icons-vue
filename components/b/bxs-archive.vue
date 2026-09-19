<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih4m8wbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih4m8wbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-archive" /></template>
