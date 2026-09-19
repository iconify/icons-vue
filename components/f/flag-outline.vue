<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf6v6g3zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6v6g3zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:flag-outline" /></template>
