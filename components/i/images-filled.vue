<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjmqsobna.css';
import '../../css/n/nlx7eybis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjmqsobna"/><path clip-rule="evenodd" class="nlx7eybis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:images-filled" /></template>
