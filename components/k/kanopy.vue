<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4gv5c79q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4gv5c79q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kanopy" /></template>
