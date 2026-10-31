<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/patrfv0we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="patrfv0we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:arrow-down" /></template>
