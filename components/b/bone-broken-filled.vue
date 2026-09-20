<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdjtlobjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdjtlobjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bone-broken-filled" /></template>
