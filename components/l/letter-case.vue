<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob47p4bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob47p4bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-case" /></template>
