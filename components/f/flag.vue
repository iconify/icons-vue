<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3e3kfp2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3e3kfp2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag" /></template>
