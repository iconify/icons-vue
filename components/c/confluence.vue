<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d75rcbs-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d75rcbs-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:confluence" /></template>
