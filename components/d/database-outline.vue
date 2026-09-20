<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og0ik0mwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og0ik0mwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-outline" /></template>
