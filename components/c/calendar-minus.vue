<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7u3bta8y.css';
import '../../css/n/nf_ef62wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7u3bta8y"/><path class="nf_ef62wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-minus" /></template>
