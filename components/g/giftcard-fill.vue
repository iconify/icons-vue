<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v43vsl3of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v43vsl3of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:giftcard-fill" /></template>
