<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhk4w5u-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhk4w5u-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:expand-vertical-light" /></template>
