<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbw7_8o6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbw7_8o6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-down" /></template>
