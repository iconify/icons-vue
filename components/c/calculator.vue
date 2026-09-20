<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcx7mn54s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-2};
const content = `<path class="kcx7mn54s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:calculator" /></template>
