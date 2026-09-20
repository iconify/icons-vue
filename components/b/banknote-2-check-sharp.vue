<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5zuveb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5zuveb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-check-sharp" /></template>
