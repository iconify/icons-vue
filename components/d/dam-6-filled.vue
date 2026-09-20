<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejyr96b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejyr96b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-6-filled" /></template>
