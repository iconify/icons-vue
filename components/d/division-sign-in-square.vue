<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_olkpbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v_olkpbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:division-sign-in-square" /></template>
