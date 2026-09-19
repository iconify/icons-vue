<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hupzjybbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hupzjybbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dot-04-l" /></template>
