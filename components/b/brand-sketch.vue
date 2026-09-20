<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg80ktboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg80ktboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-sketch" /></template>
