<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-b_zxyms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="x-b_zxyms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:call-in-26" /></template>
