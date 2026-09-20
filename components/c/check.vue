<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69bcmbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f69bcmbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:check" /></template>
