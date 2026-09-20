<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z22fae9xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z22fae9xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-spark" /></template>
