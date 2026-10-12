<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pehpq5qtd.css';
import '../../css/b/ba28ldwhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pehpq5qtd"/><path class="ba28ldwhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-minus-filled" /></template>
