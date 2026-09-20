<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkpurpbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkpurpbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:delivery-package-person-bold" /></template>
