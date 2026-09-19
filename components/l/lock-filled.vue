<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga2pkn1kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga2pkn1kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-filled" /></template>
