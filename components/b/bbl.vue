<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmu89xj2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmu89xj2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bbl" /></template>
