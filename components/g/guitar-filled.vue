<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4mtfqb_h.css';
import '../../css/r/racdv353u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4mtfqb_h"/><path class="racdv353u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:guitar-filled" /></template>
