<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tklhe1yht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tklhe1yht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:headphones" /></template>
