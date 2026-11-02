<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phvm0umma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phvm0umma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arow-to-down-line" /></template>
