<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv6fu-bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hv6fu-bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-down-square-fill" /></template>
