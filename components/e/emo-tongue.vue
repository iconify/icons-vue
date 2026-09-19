<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqr1u1-go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":824,"height":1000};
const content = `<path class="pqr1u1-go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-tongue" /></template>
