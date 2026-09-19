<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6xg8hrwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6xg8hrwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:cloud-outline" /></template>
