<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvk7-hbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvk7-hbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:amex" /></template>
