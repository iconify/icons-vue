<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twkvrxbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twkvrxbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-alt-filled" /></template>
