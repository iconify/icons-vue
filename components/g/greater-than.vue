<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecjoy0h7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecjoy0h7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:greater-than" /></template>
