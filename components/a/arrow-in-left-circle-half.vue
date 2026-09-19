<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5-5xebiw.css';
import '../../css/z/z7ybbhltq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5-5xebiw"/><path class="z7ybbhltq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-left-circle-half" /></template>
