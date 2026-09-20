<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd_4pkbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd_4pkbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-left" /></template>
