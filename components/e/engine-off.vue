<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knsyv5b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knsyv5b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:engine-off" /></template>
