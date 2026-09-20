<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrxb42skb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jrxb42skb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-11" /></template>
