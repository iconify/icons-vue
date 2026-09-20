<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_zup3_vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_zup3_vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coupon-fill" /></template>
