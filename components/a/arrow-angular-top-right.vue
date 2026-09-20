<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya8_7lb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ya8_7lb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-angular-top-right" /></template>
