<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgru19b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgru19b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:chevron-double-right" /></template>
