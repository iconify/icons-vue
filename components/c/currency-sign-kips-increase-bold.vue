<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgiih6s2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgiih6s2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:currency-sign-kips-increase-bold" /></template>
