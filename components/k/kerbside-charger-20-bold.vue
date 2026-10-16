<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl-hvjv-v.css';
import '../../css/s/sp04sxb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sl-hvjv-v"/><path class="sp04sxb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kerbside-charger-20-bold" /></template>
