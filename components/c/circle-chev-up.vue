<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqc3elbeh.css';
import '../../css/i/ih5nivq9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqc3elbeh"/><path class="ih5nivq9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-chev-up" /></template>
