<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp_4n9bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kp_4n9bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrow-up-right-and-arrow-down-left-from-center" /></template>
