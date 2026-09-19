<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i58rq-36d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i58rq-36d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-right" /></template>
