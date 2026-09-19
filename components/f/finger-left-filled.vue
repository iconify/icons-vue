<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9wwu21rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9wwu21rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-left-filled" /></template>
