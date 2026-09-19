<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6qkenbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6qkenbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dental-broken-tooth" /></template>
