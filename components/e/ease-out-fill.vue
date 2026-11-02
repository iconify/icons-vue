<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k442f7l-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k442f7l-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-out-fill" /></template>
