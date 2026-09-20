<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_toq0bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_toq0bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-sharp-fill" /></template>
