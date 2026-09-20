<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0v_txbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0v_txbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-pin-circle-fill" /></template>
