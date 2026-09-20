<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc9k5vb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc9k5vb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:caravan-fill" /></template>
