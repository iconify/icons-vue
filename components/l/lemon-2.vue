<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk72nlbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk72nlbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lemon-2" /></template>
