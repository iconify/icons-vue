<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxhx1cm-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxhx1cm-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-down-right-main" /></template>
