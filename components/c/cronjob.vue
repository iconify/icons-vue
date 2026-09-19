<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdb6-6b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdb6-6b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:cronjob" /></template>
