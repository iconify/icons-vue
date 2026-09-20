<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbq427-uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbq427-uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:braintree" /></template>
