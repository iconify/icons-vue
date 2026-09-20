<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aismqzxqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aismqzxqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:boom" /></template>
