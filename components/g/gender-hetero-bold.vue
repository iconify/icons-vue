<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihcqutbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihcqutbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:gender-hetero-bold" /></template>
