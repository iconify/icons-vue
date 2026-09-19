<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfwtp_bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gfwtp_bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:laser-gun" /></template>
