<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zysq2if3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zysq2if3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-2" /></template>
