<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zshnz-zog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zshnz-zog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:database" /></template>
