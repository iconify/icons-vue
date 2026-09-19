<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bno6c1bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bno6c1bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:amusement-park" /></template>
