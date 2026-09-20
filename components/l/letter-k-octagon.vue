<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqx5n1fdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqx5n1fdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-octagon" /></template>
