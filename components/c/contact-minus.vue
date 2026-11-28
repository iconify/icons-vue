<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnq8786rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnq8786rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contact-minus" /></template>
