<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ygw5bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ygw5bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:basket-fill" /></template>
