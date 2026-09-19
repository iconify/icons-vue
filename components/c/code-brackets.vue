<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzf88t2wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzf88t2wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:code-brackets" /></template>
