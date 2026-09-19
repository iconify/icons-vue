<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhc3jmhfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhc3jmhfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:credit-card-minus-alt-filled" /></template>
