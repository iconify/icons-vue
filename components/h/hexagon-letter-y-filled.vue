<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no8yeybbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no8yeybbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-y-filled" /></template>
