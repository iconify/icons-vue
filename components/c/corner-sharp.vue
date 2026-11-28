<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grt6yzcqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grt6yzcqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-sharp" /></template>
