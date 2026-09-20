<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djfh05m5o.css';
import '../../css/o/o6ao99dhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djfh05m5o"/><path class="o6ao99dhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:ethereum" /></template>
