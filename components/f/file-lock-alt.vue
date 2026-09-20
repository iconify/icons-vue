<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r000hfb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r000hfb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-lock-alt" /></template>
