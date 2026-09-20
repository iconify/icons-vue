<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no27z1b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no27z1b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-g" /></template>
