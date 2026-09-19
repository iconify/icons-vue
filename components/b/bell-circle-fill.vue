<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzb_9rbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zzb_9rbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bell-circle-fill" /></template>
