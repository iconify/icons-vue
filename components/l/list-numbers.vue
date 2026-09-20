<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glxfj3qif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glxfj3qif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:list-numbers" /></template>
