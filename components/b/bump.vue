<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw2xayp0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw2xayp0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bump" /></template>
