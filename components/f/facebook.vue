<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j24t_zsqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="j24t_zsqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:facebook" /></template>
