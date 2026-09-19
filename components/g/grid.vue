<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlw7c8bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlw7c8bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:grid" /></template>
