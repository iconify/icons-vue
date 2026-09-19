<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa-ko1b3h.css';
import '../../css/c/ch6_fcbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa-ko1b3h"/><path class="ch6_fcbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:book-add" /></template>
