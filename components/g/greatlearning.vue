<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3m05lbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3m05lbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:greatlearning" /></template>
