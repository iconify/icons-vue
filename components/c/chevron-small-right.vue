<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4ob6t.css';
import '../../css/s/so-from-10.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ob6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-small-right" /></template>
