<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbpgcvbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbpgcvbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-circle-fill" /></template>
