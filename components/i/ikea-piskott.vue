<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac_vddcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac_vddcjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-piskott" /></template>
