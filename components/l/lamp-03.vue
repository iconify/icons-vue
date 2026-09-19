<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzn5g7ntz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzn5g7ntz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lamp-03" /></template>
