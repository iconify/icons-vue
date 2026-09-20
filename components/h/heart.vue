<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfwt8_btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfwt8_btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:heart" /></template>
