<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcu9xnbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dcu9xnbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlei" /></template>
