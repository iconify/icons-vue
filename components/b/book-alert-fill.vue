<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okxd8xsdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okxd8xsdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-alert-fill" /></template>
