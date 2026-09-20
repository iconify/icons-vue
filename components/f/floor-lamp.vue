<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njp6pqswu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="njp6pqswu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:floor-lamp" /></template>
