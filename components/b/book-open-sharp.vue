<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6cjo_bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6cjo_bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-open-sharp" /></template>
