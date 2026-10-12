<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbvxq0xxv.css';
import '../../css/w/w8ad1sbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbvxq0xxv"/><path class="w8ad1sbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bell-plus-filled" /></template>
