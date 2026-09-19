<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbztp_o0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kbztp_o0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bell-slash-fill" /></template>
