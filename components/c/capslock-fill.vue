<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6_pksxpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s6_pksxpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:capslock-fill" /></template>
