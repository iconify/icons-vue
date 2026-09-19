<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6l7nbjig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6l7nbjig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:database-alt" /></template>
