<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc7y2bxnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="wc7y2bxnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:banknotes" /></template>
