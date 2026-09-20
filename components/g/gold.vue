<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7f9babeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7f9babeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:gold" /></template>
