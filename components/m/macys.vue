<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdm5t7wmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdm5t7wmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:macys" /></template>
