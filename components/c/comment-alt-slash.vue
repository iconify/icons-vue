<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ootklr19s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ootklr19s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-slash" /></template>
