<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er9fuob6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er9fuob6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-verify" /></template>
