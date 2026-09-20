<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqv5m4zzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nqv5m4zzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bookmark" /></template>
