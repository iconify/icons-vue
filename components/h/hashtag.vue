<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjvjtzbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjvjtzbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:hashtag" /></template>
