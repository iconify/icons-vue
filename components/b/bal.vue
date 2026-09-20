<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it4o-9bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it4o-9bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bal" /></template>
