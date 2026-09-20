<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss5orab7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss5orab7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:inspire" /></template>
