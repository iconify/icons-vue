<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6rh07h6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6rh07h6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-4" /></template>
