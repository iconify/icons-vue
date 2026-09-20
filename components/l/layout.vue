<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufbq6ycrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufbq6ycrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:layout" /></template>
