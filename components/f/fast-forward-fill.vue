<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5bphv0mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5bphv0mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:fast-forward-fill" /></template>
