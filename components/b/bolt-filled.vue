<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qll2hmf4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qll2hmf4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-filled" /></template>
