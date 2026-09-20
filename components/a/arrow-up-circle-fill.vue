<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szhnih4ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szhnih4ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-up-circle-fill" /></template>
