<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4gcrl_ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4gcrl_ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:done-light" /></template>
