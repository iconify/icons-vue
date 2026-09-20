<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvbbl6ipz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2};
const content = `<path class="qvbbl6ipz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cutter" /></template>
