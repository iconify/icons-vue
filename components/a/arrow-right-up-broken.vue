<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn_kq0bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn_kq0bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-up-broken" /></template>
