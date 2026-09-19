<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzv9k8vai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zzv9k8vai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:banknotes" /></template>
