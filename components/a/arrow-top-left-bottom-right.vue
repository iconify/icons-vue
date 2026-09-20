<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md3qw4bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md3qw4bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-left-bottom-right" /></template>
