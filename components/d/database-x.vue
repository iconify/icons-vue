<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/req006c1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="req006c1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:database-x" /></template>
